<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb8s-v9gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb8s-v9gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thor-hammer" /></template>
