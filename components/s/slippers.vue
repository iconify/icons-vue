<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsmq2s_xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsmq2s_xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slippers" /></template>
