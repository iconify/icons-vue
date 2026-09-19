<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2nd49bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2nd49bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trample" /></template>
