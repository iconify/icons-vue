<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu_afbskh.css';
import '../../css/e/eei-3cbtk.css';
import '../../css/g/gikolbcax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eu_afbskh"/><path class="eei-3cbtk"/><path class="gikolbcax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:tk-1x1" /></template>
