<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp641cc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp641cc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rhythm-line" /></template>
