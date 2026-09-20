<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtuukp9fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtuukp9fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meme-search-light" /></template>
