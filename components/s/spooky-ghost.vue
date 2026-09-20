<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idsrm2ssw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="idsrm2ssw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spooky-ghost" /></template>
