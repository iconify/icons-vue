<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_oec0bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="w_oec0bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:question-circle" /></template>
