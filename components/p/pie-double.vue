<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv-6a06tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bv-6a06tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pie-double" /></template>
