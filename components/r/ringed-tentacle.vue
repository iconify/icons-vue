<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at2ijpbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at2ijpbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ringed-tentacle" /></template>
