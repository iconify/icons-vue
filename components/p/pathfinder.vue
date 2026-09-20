<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol16gcbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol16gcbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:pathfinder" /></template>
