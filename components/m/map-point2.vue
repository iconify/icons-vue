<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr5c3fmnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr5c3fmnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-point2" /></template>
