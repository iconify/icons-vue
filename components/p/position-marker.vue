<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbba2ybbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbba2ybbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:position-marker" /></template>
