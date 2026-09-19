<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4g72kbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4g72kbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tensorflow" /></template>
