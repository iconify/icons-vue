<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyt2ebza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odyt2ebza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sand-snake" /></template>
