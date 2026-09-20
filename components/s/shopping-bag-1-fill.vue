<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpdpjxbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zpdpjxbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-1-fill" /></template>
