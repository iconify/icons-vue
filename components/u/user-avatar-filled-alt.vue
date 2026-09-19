<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sulruw6qc.css';
import '../../css/g/glr1ycbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sulruw6qc"/><path class="glr1ycbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-avatar-filled-alt" /></template>
