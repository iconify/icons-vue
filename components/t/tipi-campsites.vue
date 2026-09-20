<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6i-o7wkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s6i-o7wkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsites" /></template>
