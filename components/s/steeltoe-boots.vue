<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whyltiwta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whyltiwta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steeltoe-boots" /></template>
