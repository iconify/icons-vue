<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjq3pxauu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjq3pxauu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-good" /></template>
