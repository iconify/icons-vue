<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp1c9py_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xp1c9py_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:traffic-cone" /></template>
