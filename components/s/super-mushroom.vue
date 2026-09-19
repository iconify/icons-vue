<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl038tb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl038tb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:super-mushroom" /></template>
