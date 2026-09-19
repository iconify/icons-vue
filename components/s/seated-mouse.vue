<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7wjn1b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7wjn1b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:seated-mouse" /></template>
