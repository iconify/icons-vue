<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e910xyhfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":35};
const content = `<path class="e910xyhfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oddinpay-light" /></template>
