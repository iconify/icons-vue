<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmrf4i1uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmrf4i1uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:path-intersect" /></template>
