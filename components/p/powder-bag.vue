<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds02b5bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds02b5bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:powder-bag" /></template>
