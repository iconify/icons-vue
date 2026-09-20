<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n6daalb-j.css';
import '../../css/q/qu4x13nbg.css';
import '../../css/v/vkba6k5jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n6daalb-j"/><path class="qu4x13nbg"/><path class="vkba6k5jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:parentheses-broken" /></template>
