<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plqeeh25x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plqeeh25x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-browsers" /></template>
