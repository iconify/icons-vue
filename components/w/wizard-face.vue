<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-22zlb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-22zlb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wizard-face" /></template>
