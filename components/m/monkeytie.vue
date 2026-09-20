<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvy7w-nir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvy7w-nir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:monkeytie" /></template>
