<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/f6fu06mto.css';
import '../../css/m/m9rz3zbbf.css';
import '../../css/p/pow4bf5-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6fu06mto"/><circle class="m9rz3zbbf"/><circle class="pow4bf5-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-cancer" /></template>
