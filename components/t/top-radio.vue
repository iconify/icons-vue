<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epd-0w0kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epd-0w0kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:top-radio" /></template>
