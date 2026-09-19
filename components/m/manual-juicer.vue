<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpeemlbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vpeemlbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:manual-juicer" /></template>
