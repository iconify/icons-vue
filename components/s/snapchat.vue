<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt_9i3bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rt_9i3bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:snapchat" /></template>
