<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd39qiwhy.css';
import '../../css/i/iwqrvp1ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd39qiwhy"/><path class="iwqrvp1ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-up-bold-duotone" /></template>
