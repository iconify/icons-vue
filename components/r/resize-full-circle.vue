<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ng4k_tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d0ng4k_tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:resize-full-circle" /></template>
