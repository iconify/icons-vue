<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byzxr3b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="byzxr3b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pie-slice" /></template>
