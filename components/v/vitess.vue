<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obzk38bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obzk38bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vitess" /></template>
