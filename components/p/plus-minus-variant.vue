<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeu1gcc0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeu1gcc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-minus-variant" /></template>
