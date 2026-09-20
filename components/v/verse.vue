<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6mk2emto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p6mk2emto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:verse" /></template>
