<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke-b1vt8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ke-b1vt8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shapes" /></template>
