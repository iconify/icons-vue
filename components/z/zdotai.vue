<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpy9ok0_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpy9ok0_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zdotai" /></template>
