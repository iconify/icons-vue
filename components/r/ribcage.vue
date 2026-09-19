<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka62gcbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka62gcbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ribcage" /></template>
