<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qouqbozat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qouqbozat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-fill-round" /></template>
