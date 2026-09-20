<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjfe1bcyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kjfe1bcyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:seaplane-takeoff-over-water" /></template>
