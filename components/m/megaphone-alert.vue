<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f73t0tbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f73t0tbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:megaphone-alert" /></template>
