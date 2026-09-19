<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa_radcde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa_radcde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-collar" /></template>
