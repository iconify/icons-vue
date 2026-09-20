<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5pb0owa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wq5pb0owa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-down" /></template>
