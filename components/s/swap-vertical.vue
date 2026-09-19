<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4_nstbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4_nstbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:swap-vertical" /></template>
