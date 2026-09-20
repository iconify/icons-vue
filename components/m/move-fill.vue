<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khn9nwoel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khn9nwoel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-fill" /></template>
