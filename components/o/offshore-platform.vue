<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8v_exbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8v_exbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:offshore-platform" /></template>
