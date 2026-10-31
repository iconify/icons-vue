<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk85qacez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk85qacez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-check-fill-round" /></template>
