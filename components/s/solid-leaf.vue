<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp2j0pbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp2j0pbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:solid-leaf" /></template>
