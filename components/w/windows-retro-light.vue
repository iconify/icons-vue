<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhdlf2bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhdlf2bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-retro-light" /></template>
