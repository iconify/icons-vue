<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv4k0-y3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv4k0-y3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tree-roots" /></template>
