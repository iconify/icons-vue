<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4n3iyb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g4n3iyb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shark-dorsal-fin-in-waters" /></template>
