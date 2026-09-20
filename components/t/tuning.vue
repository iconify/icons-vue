<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ao6ebtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z4ao6ebtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tuning" /></template>
