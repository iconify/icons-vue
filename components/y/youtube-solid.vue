<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiyr906ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiyr906ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:youtube-solid" /></template>
