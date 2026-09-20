<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaw1wpsia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaw1wpsia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-start-mini-line" /></template>
