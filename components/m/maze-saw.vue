<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqteblb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqteblb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:maze-saw" /></template>
