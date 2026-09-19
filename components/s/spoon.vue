<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g18q7hdew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="g18q7hdew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spoon" /></template>
