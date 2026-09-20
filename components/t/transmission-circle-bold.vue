<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saoi0tb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="saoi0tb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-circle-bold" /></template>
