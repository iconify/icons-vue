<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftfqew1zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftfqew1zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spotted-mushroom" /></template>
