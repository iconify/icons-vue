<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otdq19b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otdq19b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:orbital" /></template>
