<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwgceku3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwgceku3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:projector-2-fill" /></template>
