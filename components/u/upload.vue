<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj8l9tbqx.css';
import '../../css/v/vqd8c7baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="nj8l9tbqx"/><path class="vqd8c7baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:upload" /></template>
