<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6az2bcvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m6az2bcvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trinacria" /></template>
