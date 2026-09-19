<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i11tn-zvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i11tn-zvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pentagram-rose" /></template>
