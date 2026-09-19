<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgn4__dfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgn4__dfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:phone-portrait-sharp" /></template>
