<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9lwr14yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9lwr14yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pineapple" /></template>
