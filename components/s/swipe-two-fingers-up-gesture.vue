<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esiznkb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esiznkb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-two-fingers-up-gesture" /></template>
