<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn05e-bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sn05e-bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:oven-mitts-minimalistic-outline" /></template>
