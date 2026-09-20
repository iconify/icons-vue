<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh3x8-bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="wh3x8-bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:statistics" /></template>
