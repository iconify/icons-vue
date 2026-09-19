<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwt0rccvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwt0rccvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:person-in-blizzard" /></template>
