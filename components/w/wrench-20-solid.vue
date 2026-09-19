<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu5m0cc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yu5m0cc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wrench-20-solid" /></template>
