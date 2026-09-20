<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csh1a7bzc.css';
import '../../css/t/tbzab391z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="csh1a7bzc"/><path class="tbzab391z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:yellow-square" /></template>
