<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4kf3rbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e4kf3rbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:town-buildings" /></template>
