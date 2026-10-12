<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bktlkzkpq.css';
import '../../css/r/roo4x4bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bktlkzkpq"/><path class="roo4x4bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-check-20" /></template>
