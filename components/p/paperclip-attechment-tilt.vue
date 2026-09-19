<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flimd_qzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flimd_qzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:paperclip-attechment-tilt" /></template>
