<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sno168bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":14};
const content = `<path class="sno168bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:subtraction" /></template>
