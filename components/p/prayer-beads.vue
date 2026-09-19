<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgrym7bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgrym7bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:prayer-beads" /></template>
