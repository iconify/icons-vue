<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrob_ccbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nrob_ccbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:six-of-bamboos-mahjong-filled" /></template>
