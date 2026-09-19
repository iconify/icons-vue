<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmc0o5h_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmc0o5h_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oyster" /></template>
