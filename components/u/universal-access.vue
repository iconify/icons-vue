<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k0-8awbkj.css';
import '../../css/i/iuy23obtc.css';
import '../../css/v/vq0zclbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="k0-8awbkj"/><path class="iuy23obtc"/><path clip-rule="evenodd" class="vq0zclbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:universal-access" /></template>
