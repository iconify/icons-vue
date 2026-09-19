<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjeykdpei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjeykdpei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rope-dart" /></template>
