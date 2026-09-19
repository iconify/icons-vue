<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp_9pbj6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pp_9pbj6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unbalanced" /></template>
