<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klo15i2iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klo15i2iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:waterfall" /></template>
