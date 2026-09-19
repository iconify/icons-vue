<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssctzqt6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ssctzqt6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:walking-boot" /></template>
