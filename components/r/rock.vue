<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn3kl9bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pn3kl9bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rock" /></template>
