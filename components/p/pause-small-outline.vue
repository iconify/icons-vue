<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uss3lth2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uss3lth2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pause-small-outline" /></template>
