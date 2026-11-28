<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsp35ou_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lsp35ou_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:satellite-dish-light" /></template>
