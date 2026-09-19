<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bicjs882a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bicjs882a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-selection" /></template>
