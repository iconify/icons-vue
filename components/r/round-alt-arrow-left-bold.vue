<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw0pllb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw0pllb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-left-bold" /></template>
