<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojkue2tvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojkue2tvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:open-wound" /></template>
