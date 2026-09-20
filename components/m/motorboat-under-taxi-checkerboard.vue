<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj--fcbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uj--fcbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-under-taxi-checkerboard" /></template>
