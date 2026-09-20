<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l893odb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l893odb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:objects" /></template>
