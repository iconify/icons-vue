<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd-sd1bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="nd-sd1bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rail-metro-11" /></template>
