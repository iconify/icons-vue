<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j31ia0zva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j31ia0zva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-open-light" /></template>
