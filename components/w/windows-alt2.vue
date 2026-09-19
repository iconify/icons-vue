<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycfcbpy_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ycfcbpy_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:windows-alt2" /></template>
