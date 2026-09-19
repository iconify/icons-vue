<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6-v5-b8g.css';
import '../../css/s/spmrb2bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6-v5-b8g"/><path class="spmrb2bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shirt-sharp" /></template>
