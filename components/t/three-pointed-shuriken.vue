<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmiv46s4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmiv46s4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:three-pointed-shuriken" /></template>
