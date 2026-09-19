<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-rjfpb9o.css';
import '../../css/x/xyso4-t-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="i-rjfpb9o"/><path class="xyso4-t-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:swarm" /></template>
