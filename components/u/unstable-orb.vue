<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sld3gxbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sld3gxbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unstable-orb" /></template>
