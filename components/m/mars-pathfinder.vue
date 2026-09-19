<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5i_jebpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5i_jebpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mars-pathfinder" /></template>
