<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3odx4w7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m3odx4w7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:recruitment-management" /></template>
