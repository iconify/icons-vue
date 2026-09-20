<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uibiluaqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uibiluaqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-minimalistic-outline" /></template>
