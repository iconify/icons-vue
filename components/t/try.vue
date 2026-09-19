<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tus8v7snr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1408};
const content = `<path class="tus8v7snr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:try" /></template>
