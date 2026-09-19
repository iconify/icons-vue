<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mesj8d27e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mesj8d27e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pizza" /></template>
