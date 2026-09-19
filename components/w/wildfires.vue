<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf53ypbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf53ypbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wildfires" /></template>
