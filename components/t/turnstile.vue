<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncmxldb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncmxldb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:turnstile" /></template>
