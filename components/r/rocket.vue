<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsa1ivb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsa1ivb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:rocket" /></template>
