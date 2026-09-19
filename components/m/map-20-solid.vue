<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t084e5b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t084e5b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:map-20-solid" /></template>
