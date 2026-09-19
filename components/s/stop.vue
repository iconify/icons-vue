<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dthzkk69i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dthzkk69i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:stop" /></template>
