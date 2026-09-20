<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5xo13bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5xo13bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wink-solid" /></template>
