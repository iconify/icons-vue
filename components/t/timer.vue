<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdbl4xbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdbl4xbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:timer" /></template>
