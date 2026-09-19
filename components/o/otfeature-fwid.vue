<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2b7a6_zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l2b7a6_zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-fwid" /></template>
