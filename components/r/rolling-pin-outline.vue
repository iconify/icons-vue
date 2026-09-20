<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4fbtxb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4fbtxb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rolling-pin-outline" /></template>
