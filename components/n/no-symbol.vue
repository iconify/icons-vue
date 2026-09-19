<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d06mnnbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d06mnnbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:no-symbol" /></template>
