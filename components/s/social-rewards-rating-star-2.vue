<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gilwy0bbh.css';
import '../../css/m/m0qgp2bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gilwy0bbh"/><path class="m0qgp2bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-rating-star-2" /></template>
