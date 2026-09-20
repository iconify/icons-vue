<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl2cigbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl2cigbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sparkling-2-fill" /></template>
