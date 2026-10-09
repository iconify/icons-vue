<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6l3rqbjj.css';
import '../../css/q/qzqnbpaip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6l3rqbjj"/><path class="qzqnbpaip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-desc-20-bold" /></template>
