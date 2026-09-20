<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-ixubsz.css';
import '../../css/r/r8xkjtbka.css';
import '../../css/p/pnqtkcbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf-ixubsz"/><path class="r8xkjtbka"/><path class="pnqtkcbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stackspin" /></template>
