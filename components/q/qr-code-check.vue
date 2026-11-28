<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc8wbgb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8wbgb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:qr-code-check" /></template>
