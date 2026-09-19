<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_fswb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nr_fswb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vr-headset" /></template>
