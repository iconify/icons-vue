<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kakrw9-lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kakrw9-lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pay-circle-o" /></template>
