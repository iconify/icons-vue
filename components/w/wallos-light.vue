<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb05267ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb05267ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wallos-light" /></template>
