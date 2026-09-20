<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq0k25o0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kq0k25o0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:mail" /></template>
