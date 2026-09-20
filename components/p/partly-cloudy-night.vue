<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwlv0fbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qwlv0fbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:partly-cloudy-night" /></template>
