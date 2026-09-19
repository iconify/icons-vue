<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szgoh98oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szgoh98oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:private" /></template>
