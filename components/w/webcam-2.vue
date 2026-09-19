<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnx2e5jvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hnx2e5jvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:webcam-2" /></template>
