<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvj-yxi8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvj-yxi8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:miracle-medecine" /></template>
