<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4xrj7b1v.css';
import '../../css/f/fxwu97ass.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4xrj7b1v"/><path class="fxwu97ass"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:timetagger" /></template>
