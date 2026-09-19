<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu-74desw.css';
import '../../css/t/ty2vo4ljz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu-74desw"/><path class="ty2vo4ljz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:soccer" /></template>
