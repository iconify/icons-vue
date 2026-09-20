<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axybpsqfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axybpsqfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tails" /></template>
