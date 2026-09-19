<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u60y3o5nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u60y3o5nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:moon-20-solid" /></template>
