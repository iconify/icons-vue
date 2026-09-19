<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_h70ea7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z_h70ea7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:table-cells-large" /></template>
