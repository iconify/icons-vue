<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nucez9s0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nucez9s0v wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:more-vertical-sketch" /></template>
