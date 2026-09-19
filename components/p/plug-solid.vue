<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf9uo9box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wf9uo9box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:plug-solid" /></template>
