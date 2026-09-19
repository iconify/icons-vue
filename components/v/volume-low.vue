<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syt3s17lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="syt3s17lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:volume-low" /></template>
