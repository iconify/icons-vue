<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztp720b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ztp720b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-function" /></template>
