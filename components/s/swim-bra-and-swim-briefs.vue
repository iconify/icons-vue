<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iikbevq3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iikbevq3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:swim-bra-and-swim-briefs" /></template>
