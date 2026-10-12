<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s40eeqnvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s40eeqnvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-pi-filled" /></template>
