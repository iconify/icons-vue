<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz7wkfxio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uz7wkfxio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:option-key-20-bold" /></template>
