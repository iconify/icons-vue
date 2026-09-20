<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6dew0bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6dew0bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-10-line" /></template>
