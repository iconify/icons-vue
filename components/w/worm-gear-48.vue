<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj8ilnbfl.css';
import '../../css/i/i7ws4lb4n.css';
import '../../css/c/cn0l77biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nj8ilnbfl"/><path class="i7ws4lb4n"/><path class="cn0l77biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:worm-gear-48" /></template>
