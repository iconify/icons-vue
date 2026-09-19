<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apucl2q8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="apucl2q8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pocket-radio" /></template>
