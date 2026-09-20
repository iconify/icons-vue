<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmerqls6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmerqls6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:pause" /></template>
