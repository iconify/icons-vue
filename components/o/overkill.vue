<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enhro2a4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="enhro2a4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:overkill" /></template>
