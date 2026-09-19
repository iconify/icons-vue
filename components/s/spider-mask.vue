<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/senfqqftq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="senfqqftq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spider-mask" /></template>
