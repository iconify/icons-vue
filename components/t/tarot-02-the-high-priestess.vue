<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcxvwfrdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcxvwfrdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-02-the-high-priestess" /></template>
