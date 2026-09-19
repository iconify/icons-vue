<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x880s-uzh.css';
import '../../css/t/t5_14z-jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x880s-uzh"/><path class="t5_14z-jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:redheart" /></template>
