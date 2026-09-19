<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua69cksbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ua69cksbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wave-crest" /></template>
