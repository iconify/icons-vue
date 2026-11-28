<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckfbvlb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ckfbvlb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-slash-fill" /></template>
