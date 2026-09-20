<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aumdvgb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aumdvgb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:obelisk" /></template>
