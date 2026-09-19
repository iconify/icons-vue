<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsnd0qbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsnd0qbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sound-off" /></template>
