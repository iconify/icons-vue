<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0-xwh2pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r0-xwh2pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-exists-fill-12" /></template>
