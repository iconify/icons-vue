<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmk_r7b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmk_r7b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:yoga-bridge-pose-2-bold" /></template>
