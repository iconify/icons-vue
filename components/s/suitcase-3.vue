<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzrryjb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzrryjb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:suitcase-3" /></template>
