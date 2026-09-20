<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6f9-1jwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6f9-1jwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:submarine" /></template>
