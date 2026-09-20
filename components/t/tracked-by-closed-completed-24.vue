<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilw1vqb3q.css';
import '../../css/m/mtfwbcc5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilw1vqb3q"/><path class="mtfwbcc5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tracked-by-closed-completed-24" /></template>
