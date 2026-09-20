<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol2ps3w7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol2ps3w7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:switch-horizontal" /></template>
