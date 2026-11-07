<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uskchin6p.css';
import '../../css/r/rij0rxuxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uskchin6p"/><path clip-rule="evenodd" class="rij0rxuxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:waterdrop-outline" /></template>
