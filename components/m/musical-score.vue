<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi28eccsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pi28eccsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:musical-score" /></template>
