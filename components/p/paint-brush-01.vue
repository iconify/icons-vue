<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr3rnzvyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr3rnzvyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paint-brush-01" /></template>
