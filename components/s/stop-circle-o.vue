<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdt3dxbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="sdt3dxbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stop-circle-o" /></template>
