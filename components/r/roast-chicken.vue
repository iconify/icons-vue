<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_f_lgiel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_f_lgiel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:roast-chicken" /></template>
