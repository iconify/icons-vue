<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwmy0xrfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwmy0xrfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:watch" /></template>
