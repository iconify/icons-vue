<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy2e0xhtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xy2e0xhtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-han-latin" /></template>
