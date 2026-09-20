<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb7cp-bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb7cp-bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-square-line" /></template>
