<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw7imihcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pw7imihcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-in-eaved-gabled-shelter" /></template>
