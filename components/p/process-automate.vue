<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2cjnacdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t2cjnacdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:process-automate" /></template>
