<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i75-_3t5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i75-_3t5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume-medium" /></template>
