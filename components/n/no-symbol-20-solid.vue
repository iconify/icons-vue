<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uky4vab5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uky4vab5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:no-symbol-20-solid" /></template>
