<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx4ngrbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dx4ngrbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:turtle-thin" /></template>
