<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s09ali37c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s09ali37c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shapes-line" /></template>
