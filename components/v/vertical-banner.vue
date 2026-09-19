<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb96msy1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lb96msy1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vertical-banner" /></template>
