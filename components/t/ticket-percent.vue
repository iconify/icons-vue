<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/a/awo16gfmb.css';
import '../../css/i/ib9nf2tbe.css';
import '../../css/g/gvqb6nmyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="awo16gfmb"/><path class="ib9nf2tbe"/><path class="gvqb6nmyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:ticket-percent" /></template>
