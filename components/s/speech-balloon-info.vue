<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r02q42ccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r02q42ccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-info" /></template>
