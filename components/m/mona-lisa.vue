<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c81vt37sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c81vt37sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mona-lisa" /></template>
