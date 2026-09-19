<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtddmc8gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mtddmc8gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:percentage-filled" /></template>
