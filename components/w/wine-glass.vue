<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4kg44eqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kg44eqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wine-glass" /></template>
