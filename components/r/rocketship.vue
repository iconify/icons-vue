<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh3wbdc-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sh3wbdc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rocketship" /></template>
