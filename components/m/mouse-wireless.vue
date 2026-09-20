<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhamngbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rhamngbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mouse-wireless" /></template>
