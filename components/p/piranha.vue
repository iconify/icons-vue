<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flyk9bcml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flyk9bcml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:piranha" /></template>
