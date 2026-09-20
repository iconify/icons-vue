<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g81s1jb6y.css';
import '../../css/t/t0v9d0zwi.css';
import '../../css/d/d45sk0bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g81s1jb6y"/><path class="t0v9d0zwi"/><path class="d45sk0bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:vectors-add-anchor" /></template>
