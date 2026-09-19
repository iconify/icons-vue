<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv-vfzv2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mv-vfzv2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:zeus-sword" /></template>
