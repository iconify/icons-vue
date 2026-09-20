<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgnzx4bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgnzx4bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:treasure-map-fill" /></template>
