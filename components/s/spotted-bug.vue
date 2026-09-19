<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey2vr05ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey2vr05ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spotted-bug" /></template>
