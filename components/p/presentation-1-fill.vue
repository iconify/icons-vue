<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot7fqob2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot7fqob2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-1-fill" /></template>
