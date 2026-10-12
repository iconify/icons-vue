<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2qr6x11y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n2qr6x11y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:quote-stroke-20" /></template>
