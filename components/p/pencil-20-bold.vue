<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg2rt9b6k.css';
import '../../css/c/cthax4bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cg2rt9b6k"/><path class="cthax4bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pencil-20-bold" /></template>
