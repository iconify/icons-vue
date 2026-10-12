<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arac5xnmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arac5xnmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ruler-dimension-line-filled" /></template>
