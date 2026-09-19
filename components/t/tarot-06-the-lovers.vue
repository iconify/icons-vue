<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aphd_b-zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aphd_b-zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-06-the-lovers" /></template>
