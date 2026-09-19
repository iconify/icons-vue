<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocgeu8bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocgeu8bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-glass" /></template>
