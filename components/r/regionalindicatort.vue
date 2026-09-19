<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9szmoya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="go9szmoya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatort" /></template>
