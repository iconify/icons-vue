<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv2opow9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iv2opow9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-low-solid" /></template>
