<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ny_92rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ny_92rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reddit-fill" /></template>
