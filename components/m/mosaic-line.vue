<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zef4ti3ay.css';
import '../../css/k/k63q7xktr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zef4ti3ay"/><path class="k63q7xktr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mosaic-line" /></template>
