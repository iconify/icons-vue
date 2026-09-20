<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt44b3btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt44b3btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:umbrella-line" /></template>
