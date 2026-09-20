<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jipz93b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jipz93b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:webcam-filled" /></template>
