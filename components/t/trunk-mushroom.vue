<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddog7m7_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ddog7m7_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trunk-mushroom" /></template>
