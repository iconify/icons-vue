<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkyy27shr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkyy27shr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mushroom-outline" /></template>
