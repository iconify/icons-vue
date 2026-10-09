<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwm1rebcn.css';
import '../../css/v/vc21ghbwp.css';
import '../../css/n/nfrz65yag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwm1rebcn"/><path class="vc21ghbwp"/><path class="nfrz65yag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rainbow-20-bold" /></template>
