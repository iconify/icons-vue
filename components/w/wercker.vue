<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhul_5x-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qhul_5x-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wercker" /></template>
