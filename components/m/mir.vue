<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_-xvvo4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":80,"left":36,"top":112};
const content = `<path class="l_-xvvo4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mir" /></template>
