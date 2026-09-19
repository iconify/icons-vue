<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilzi5vbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilzi5vbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striking-balls" /></template>
