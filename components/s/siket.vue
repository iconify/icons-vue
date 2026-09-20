<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdf8mjbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":214,"height":308};
const content = `<path class="sdf8mjbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:siket" /></template>
