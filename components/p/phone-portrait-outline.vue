<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8xwu9g6i.css';
import '../../css/g/gxciwdbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="s8xwu9g6i"/><path class="gxciwdbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:phone-portrait-outline" /></template>
