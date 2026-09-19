<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipss57bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipss57bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:padlock-open" /></template>
