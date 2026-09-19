<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ori6jp11a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ori6jp11a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ranch-gate" /></template>
