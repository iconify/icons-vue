<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5-unvbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5-unvbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wing-cloak" /></template>
