<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r099o0npj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r099o0npj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:person" /></template>
