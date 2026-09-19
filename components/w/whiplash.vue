<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9yl2xtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="li9yl2xtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whiplash" /></template>
