<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol6f-pyhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ol6f-pyhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pretzel" /></template>
