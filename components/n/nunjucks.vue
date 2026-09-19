<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu5o7c14i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tu5o7c14i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nunjucks" /></template>
