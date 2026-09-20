<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz-dpjbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-dpjbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rotary-international" /></template>
