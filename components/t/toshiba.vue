<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz96o9b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iz96o9b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:toshiba" /></template>
