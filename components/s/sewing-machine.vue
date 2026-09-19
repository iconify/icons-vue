<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix08evpeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix08evpeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sewing-machine" /></template>
