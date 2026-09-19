<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvogycc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvogycc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pool-dive" /></template>
