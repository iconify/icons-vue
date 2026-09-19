<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crxz9v-3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crxz9v-3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pause-filled" /></template>
