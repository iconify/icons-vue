<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx31-920e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="vx31-920e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:snowmobile-11" /></template>
