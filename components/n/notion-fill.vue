<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_-10c8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_-10c8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notion-fill" /></template>
