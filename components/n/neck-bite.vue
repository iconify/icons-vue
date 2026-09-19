<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2z222b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t2z222b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:neck-bite" /></template>
