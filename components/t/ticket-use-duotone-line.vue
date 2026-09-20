<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwb0gcbpy.css';
import '../../css/o/o02y6724p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwb0gcbpy"/><path class="o02y6724p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ticket-use-duotone-line" /></template>
