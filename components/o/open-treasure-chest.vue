<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfjdu186i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfjdu186i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:open-treasure-chest" /></template>
