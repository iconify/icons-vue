<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm4edqt9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sm4edqt9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sextant" /></template>
