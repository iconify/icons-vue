<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjo077brx.css';
import '../../css/x/x4_qz_bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="qjo077brx"/><path class="x4_qz_bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:watch-11" /></template>
