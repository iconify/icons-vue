<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvifkjfwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1664};
const content = `<path class="uvifkjfwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pied-piper" /></template>
