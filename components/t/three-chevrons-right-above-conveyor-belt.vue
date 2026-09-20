<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyjstn5af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hyjstn5af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-chevrons-right-above-conveyor-belt" /></template>
