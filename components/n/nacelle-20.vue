<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjzhse32s.css';
import '../../css/y/y-a7xo-fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mjzhse32s"/><path class="y-a7xo-fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nacelle-20" /></template>
