<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt59dgbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt59dgbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smile-circle-bold" /></template>
