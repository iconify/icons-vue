<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgsb5nhjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgsb5nhjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:panda" /></template>
