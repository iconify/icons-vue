<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_8-i3bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_8-i3bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:task-line" /></template>
