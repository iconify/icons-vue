<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxwxdtx4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gxwxdtx4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:sort-descending" /></template>
