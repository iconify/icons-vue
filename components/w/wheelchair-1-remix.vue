<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnsw0ab6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mnsw0ab6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wheelchair-1-remix" /></template>
