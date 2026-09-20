<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqim5fb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="wqim5fb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:radio" /></template>
