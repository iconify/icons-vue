<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2c_bsglq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2c_bsglq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:user-sad" /></template>
