<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou25alb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ou25alb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mp3-16" /></template>
