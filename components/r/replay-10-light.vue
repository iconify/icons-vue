<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cee5okbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cee5okbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:replay-10-light" /></template>
