<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_o2s1b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="g_o2s1b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:plane" /></template>
