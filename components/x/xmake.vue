<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5f350l-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5f350l-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:xmake" /></template>
