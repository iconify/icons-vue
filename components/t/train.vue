<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umng054pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="umng054pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:train" /></template>
