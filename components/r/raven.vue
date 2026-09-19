<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndt2mhb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ndt2mhb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:raven" /></template>
