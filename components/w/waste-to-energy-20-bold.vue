<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbxu_906s.css';
import '../../css/f/f9aktpbth.css';
import '../../css/p/p8fzstjth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vbxu_906s"/><path class="f9aktpbth"/><path class="p8fzstjth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waste-to-energy-20-bold" /></template>
