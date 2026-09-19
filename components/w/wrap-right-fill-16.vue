<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-llofvpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-llofvpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-right-fill-16" /></template>
