<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz-ie_bjg.css';
import '../../css/f/f9id0oq2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cz-ie_bjg"/><path class="f9id0oq2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:newmoon" /></template>
