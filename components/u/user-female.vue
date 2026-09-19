<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5_nc9h-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a5_nc9h-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:user-female" /></template>
