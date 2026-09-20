<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujkfyy2pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujkfyy2pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-alias" /></template>
