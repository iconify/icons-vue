<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9t41hb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9t41hb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-settings" /></template>
