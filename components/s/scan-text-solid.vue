<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/divu5xtco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="divu5xtco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-text-solid" /></template>
