<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnmudmb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cnmudmb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steel-claws" /></template>
