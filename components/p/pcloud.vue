<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5n0tdbry.css';
import '../../css/v/vfy3xytew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5n0tdbry"/><path class="vfy3xytew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pcloud" /></template>
