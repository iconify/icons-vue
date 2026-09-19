<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9d5777lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="z9d5777lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:notificationbottom" /></template>
