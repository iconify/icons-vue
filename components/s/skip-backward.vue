<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvfwumb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvfwumb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:skip-backward" /></template>
