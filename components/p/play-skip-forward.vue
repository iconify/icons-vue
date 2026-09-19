<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prqx2yctb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prqx2yctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-skip-forward" /></template>
