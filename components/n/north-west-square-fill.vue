<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi8hw16yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi8hw16yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-square-fill" /></template>
