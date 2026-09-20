<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9a78jban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9a78jban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smart-card" /></template>
