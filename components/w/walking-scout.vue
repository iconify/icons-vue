<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgu-vcc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgu-vcc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:walking-scout" /></template>
