<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhknwb6nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yhknwb6nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oregon" /></template>
