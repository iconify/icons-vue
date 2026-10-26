<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loraotb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":35};
const content = `<path class="loraotb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oddinpay-dark" /></template>
