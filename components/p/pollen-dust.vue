<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhbx1kb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhbx1kb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pollen-dust" /></template>
