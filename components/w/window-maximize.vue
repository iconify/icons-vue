<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgcl4rbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgcl4rbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:window-maximize" /></template>
