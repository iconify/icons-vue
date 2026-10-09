<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1c9zmbsp.css';
import '../../css/s/scp3oyb1s.css';
import '../../css/t/tp54fz-fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1c9zmbsp"/><path class="scp3oyb1s"/><path class="tp54fz-fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-up-20-bold" /></template>
