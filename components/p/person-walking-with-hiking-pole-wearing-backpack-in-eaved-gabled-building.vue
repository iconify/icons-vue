<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk_d2pbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yk_d2pbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-with-hiking-pole-wearing-backpack-in-eaved-gabled-building" /></template>
