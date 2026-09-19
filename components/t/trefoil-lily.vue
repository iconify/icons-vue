<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgb51vb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgb51vb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trefoil-lily" /></template>
