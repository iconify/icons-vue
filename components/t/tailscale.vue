<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2kgbvb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2kgbvb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tailscale" /></template>
