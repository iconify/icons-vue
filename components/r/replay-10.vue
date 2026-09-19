<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9i1nc98d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="u9i1nc98d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:replay-10" /></template>
