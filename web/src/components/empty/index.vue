<template>
    <div class="cw-empty">
        {{ label }}
    </div>
</template>

<script>
/**
 * +----------------------------------------------------------------------
 * | 「e家宜业」 —— 助力物业服务升级，用心服务万千业主
 * +----------------------------------------------------------------------
 * | Copyright (c) 2020~2021 https://www.chowa.com All rights reserved.
 * +----------------------------------------------------------------------
 * | Licensed 未经许可不能去掉「e家宜业」和「卓瓦科技」相关版权
 * +----------------------------------------------------------------------
 * | Author: jixuecong@chowa.cn
 * +----------------------------------------------------------------------
 */

export default {
    name: 'Empty',
    props: {
        label: String
    }
};
</script>

<style lang="less">
.cw-empty {
    text-align: center;
    font-size: 12px;
    color: #999;
    line-height: 40px;
}
</style>
