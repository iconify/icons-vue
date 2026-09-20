<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr8ng8mre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="dr8ng8mre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:move" /></template>
