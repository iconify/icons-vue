<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa2d64-ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa2d64-ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sun-light" /></template>
