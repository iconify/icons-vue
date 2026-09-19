<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgk_xe5yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgk_xe5yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rolling-energy" /></template>
