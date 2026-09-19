<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc0-4x45x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc0-4x45x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:usable" /></template>
