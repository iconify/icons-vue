<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu5_bjb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu5_bjb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rtm" /></template>
