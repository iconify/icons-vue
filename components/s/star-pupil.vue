<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puvkz5bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puvkz5bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-pupil" /></template>
