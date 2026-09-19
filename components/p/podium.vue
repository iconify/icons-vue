<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca-7h_wwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":771,"height":1024};
const content = `<path class="ca-7h_wwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:podium" /></template>
