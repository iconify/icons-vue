<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7xqt_bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7xqt_bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sun" /></template>
