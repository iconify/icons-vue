<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov6u5_g5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov6u5_g5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:morgue-feet" /></template>
