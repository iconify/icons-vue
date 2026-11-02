<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/h/hek03ebjy.css';
import '../../css/a/azso1xmvh.css';
import '../../css/s/sjhb3lgcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="hek03ebjy"/><path class="azso1xmvh"/><path class="sjhb3lgcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:waves" /></template>
