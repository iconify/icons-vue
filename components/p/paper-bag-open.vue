<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjs4webtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjs4webtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-bag-open" /></template>
