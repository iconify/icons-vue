<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czhwh68px.css';
import '../../css/n/n4x3x3ysu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="czhwh68px"/><path class="n4x3x3ysu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:watch-sharp" /></template>
