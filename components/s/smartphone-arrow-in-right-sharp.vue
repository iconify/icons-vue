<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfsa7m3yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfsa7m3yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-right-sharp" /></template>
