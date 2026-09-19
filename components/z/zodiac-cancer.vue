<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pow4bf5-z.css';
import '../../css/m/m9rz3zbbf.css';
import '../../css/p/p3ymykbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="pow4bf5-z"/><circle transform="rotate(180 17.5 14.5)" class="m9rz3zbbf"/><path class="p3ymykbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zodiac-cancer" /></template>
