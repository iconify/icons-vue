<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1t0vjbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f1t0vjbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-4-outline" /></template>
