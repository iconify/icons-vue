<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og1rtpbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="og1rtpbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tired" /></template>
