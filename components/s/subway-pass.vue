<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m__u_xbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m__u_xbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:subway-pass" /></template>
