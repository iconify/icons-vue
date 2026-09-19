<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrrpgk59a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lrrpgk59a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spinning-ribbons" /></template>
