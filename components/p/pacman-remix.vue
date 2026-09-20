<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd8rjt12r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bd8rjt12r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pacman-remix" /></template>
