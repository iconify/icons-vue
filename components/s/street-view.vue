<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm24th03j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm24th03j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:street-view" /></template>
