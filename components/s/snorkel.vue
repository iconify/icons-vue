<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il6k9zb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il6k9zb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snorkel" /></template>
