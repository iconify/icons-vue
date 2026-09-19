<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnf4jb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqnf4jb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:missile-swarm" /></template>
