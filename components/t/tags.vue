<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vplsskzdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vplsskzdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:tags" /></template>
