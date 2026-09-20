<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp38xqa3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp38xqa3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-lock-line" /></template>
