<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucsybziaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucsybziaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mug-shot" /></template>
