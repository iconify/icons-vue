<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw-u0abrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dw-u0abrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:menu" /></template>
