<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smtdp5bbp.css';
import '../../css/i/i423b8lay.css';
import '../../css/p/plefd-99d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":445,"height":168};
const content = `<path class="smtdp5bbp"/><path class="i423b8lay"/><path class="plefd-99d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:skechers" /></template>
