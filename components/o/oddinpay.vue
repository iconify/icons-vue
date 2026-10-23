<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc87pduwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":35};
const content = `<path class="uc87pduwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oddinpay" /></template>
