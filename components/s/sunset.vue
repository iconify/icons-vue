<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/app7u2h4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="app7u2h4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sunset" /></template>
