<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7nd9-vlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7nd9-vlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swordman" /></template>
