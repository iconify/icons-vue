<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12x9ab0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x12x9ab0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:settings-2-filled" /></template>
