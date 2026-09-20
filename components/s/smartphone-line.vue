<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtuoe68jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtuoe68jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:smartphone-line" /></template>
