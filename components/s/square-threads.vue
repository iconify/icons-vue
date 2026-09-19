<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h89o8pbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h89o8pbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-threads" /></template>
