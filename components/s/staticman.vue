<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea92e7bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ea92e7bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:staticman" /></template>
