<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_971ftw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vh_971ftw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:private-first-class" /></template>
