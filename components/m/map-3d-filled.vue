<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ron-o7_wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ron-o7_wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-3d-filled" /></template>
