<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv60hwb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv60hwb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ticket-percent" /></template>
