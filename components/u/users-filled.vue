<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg3_5yc3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3_5yc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:users-filled" /></template>
