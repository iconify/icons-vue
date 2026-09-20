<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayzsdqbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ayzsdqbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-house-with-flag" /></template>
