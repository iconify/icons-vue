<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yal-1qa0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yal-1qa0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pdf-file" /></template>
