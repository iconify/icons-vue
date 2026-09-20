<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxftx6b1l.css';
import '../../css/n/ncu40jb7n.css';
import '../../css/m/m6donjb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxftx6b1l"/><path class="ncu40jb7n"/><path class="m6donjb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-verge" /></template>
