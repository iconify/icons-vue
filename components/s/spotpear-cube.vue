<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai2ywhbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai2ywhbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotpear-cube" /></template>
