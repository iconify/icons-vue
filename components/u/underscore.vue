<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsh5-wo2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":524,"height":797};
const content = `<path class="bsh5-wo2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:underscore" /></template>
