<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w040a9bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w040a9bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:octoprint" /></template>
