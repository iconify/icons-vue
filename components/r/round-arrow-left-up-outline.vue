<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i94zsefas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i94zsefas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-up-outline" /></template>
