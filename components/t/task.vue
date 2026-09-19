<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4l5a2vcw.css';
import '../../css/h/h40gxbcln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4l5a2vcw"/><path class="h40gxbcln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:task" /></template>
