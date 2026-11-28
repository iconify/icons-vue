<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqi0kxbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zqi0kxbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:steak-bold" /></template>
