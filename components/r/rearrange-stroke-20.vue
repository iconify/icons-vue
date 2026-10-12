<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usonzhgnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="usonzhgnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rearrange-stroke-20" /></template>
