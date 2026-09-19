<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7s11ybex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7s11ybex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rectangle-goggles" /></template>
