<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk4nvcbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk4nvcbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tree-line" /></template>
