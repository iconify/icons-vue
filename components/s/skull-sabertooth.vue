<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukd08s7uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukd08s7uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skull-sabertooth" /></template>
