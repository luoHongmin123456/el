<template>
    <div>
        <el-dialog title="添加用户" :visible.sync="showAdd.show">
            <div slot="footer" class="dialog-footer">
                <el-button @click="showAdd.show=false">取 消</el-button>
                <el-button type="primary" @click="showAdd.show=false">添加</el-button>
            </div>
        </el-dialog>
    </div>
</template>
<script>
export default {
    props:['showAdd']
}
</script>