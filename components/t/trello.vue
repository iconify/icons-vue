<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgc52eqtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgc52eqtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:trello" /></template>
