<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qvdpjlbmz.css';
import '../../css/y/yv7vu1bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qvdpjlbmz"/><path class="yv7vu1bvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ms-powerpoint-solid" /></template>
