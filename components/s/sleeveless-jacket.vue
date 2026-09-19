<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtr-b-c8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtr-b-c8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sleeveless-jacket" /></template>
