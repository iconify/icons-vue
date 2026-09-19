<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1n7stbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1n7stbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:traffic-cone" /></template>
