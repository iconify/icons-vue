<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlazx1s9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nlazx1s9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:subtitle" /></template>
