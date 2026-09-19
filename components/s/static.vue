<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxe0aobvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kxe0aobvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:static" /></template>
