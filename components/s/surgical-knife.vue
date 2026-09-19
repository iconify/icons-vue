<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw4g0-bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="qw4g0-bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:surgical-knife" /></template>
