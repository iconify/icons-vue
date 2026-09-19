<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgpsre80s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgpsre80s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:supersonic-arrow" /></template>
