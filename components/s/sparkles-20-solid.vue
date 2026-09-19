<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg5y5bc5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fg5y5bc5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sparkles-20-solid" /></template>
