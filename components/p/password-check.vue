<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbd_w18hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbd_w18hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:password-check" /></template>
