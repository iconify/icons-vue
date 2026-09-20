<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shbp87bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="shbp87bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:outbox" /></template>
