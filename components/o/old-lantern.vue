<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-tfosij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms-tfosij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:old-lantern" /></template>
