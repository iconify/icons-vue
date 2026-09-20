<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj82rt0pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj82rt0pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:nightstand3" /></template>
