<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b6g9lcbgc.css';
import '../../css/p/p3qnk6m6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="b6g9lcbgc"/><path class="p3qnk6m6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-close-duotone" /></template>
