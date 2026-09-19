<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nemn_ba6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nemn_ba6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pin" /></template>
