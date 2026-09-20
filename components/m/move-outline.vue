<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl5mm0lik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl5mm0lik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-outline" /></template>
