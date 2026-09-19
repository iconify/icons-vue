<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adqn4c7sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adqn4c7sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:person-in-bed" /></template>
