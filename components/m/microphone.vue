<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgwq5j0zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgwq5j0zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:microphone" /></template>
