<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klnqmk2mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klnqmk2mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-dot-bold" /></template>
