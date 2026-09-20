<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quzra8ibi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzra8ibi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:time-duration-fill" /></template>
