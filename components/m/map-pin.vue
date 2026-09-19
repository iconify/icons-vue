<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgxkgcndv.css';
import '../../css/e/e5703z3pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgxkgcndv"/><path class="e5703z3pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:map-pin" /></template>
