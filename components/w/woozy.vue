<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v61t93bzx.css';
import '../../css/y/yxz7n2ipb.css';
import '../../css/s/siob3cbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="v61t93bzx"/><path clip-rule="evenodd" class="yxz7n2ipb"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:woozy" /></template>
