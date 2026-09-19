<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la181rmii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="la181rmii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-landscape" /></template>
