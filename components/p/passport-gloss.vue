<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1hh1cjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1hh1cjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:passport-gloss" /></template>
