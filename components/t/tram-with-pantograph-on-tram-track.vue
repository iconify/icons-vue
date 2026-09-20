<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8ys20bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k8ys20bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tram-with-pantograph-on-tram-track" /></template>
