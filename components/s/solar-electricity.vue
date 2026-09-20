<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1fz6jjjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1fz6jjjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:solar-electricity" /></template>
