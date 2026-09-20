<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de9rmfxkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="de9rmfxkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:printables" /></template>
