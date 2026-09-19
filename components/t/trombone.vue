<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4yn5dlwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4yn5dlwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trombone" /></template>
