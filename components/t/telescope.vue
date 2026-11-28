<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bxmd5va3c.css';
import '../../css/c/c7woc6bam.css';
import '../../css/q/qwe7xyill.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bxmd5va3c"/><path class="c7woc6bam"/><path class="qwe7xyill"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:telescope" /></template>
