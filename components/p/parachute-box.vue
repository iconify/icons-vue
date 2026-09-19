<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4yz3fbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4yz3fbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:parachute-box" /></template>
