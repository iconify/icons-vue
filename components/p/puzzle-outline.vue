<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltmuz0bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmuz0bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:puzzle-outline" /></template>
