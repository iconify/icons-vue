<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cww7r3ejt.css';
import '../../css/t/tt10iz6wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="cww7r3ejt"/><path class="tt10iz6wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:redo" /></template>
