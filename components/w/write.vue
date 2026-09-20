<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edw-f3fjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edw-f3fjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:write" /></template>
