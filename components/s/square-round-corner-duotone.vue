<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmfepibel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmfepibel primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-round-corner-duotone" /></template>
