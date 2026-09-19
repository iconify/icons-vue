<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlp174b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlp174b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stapler-pneumatic" /></template>
