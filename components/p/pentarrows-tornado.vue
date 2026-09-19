<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hilva9bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hilva9bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pentarrows-tornado" /></template>
