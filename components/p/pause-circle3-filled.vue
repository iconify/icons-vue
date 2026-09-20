<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghtw4bbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghtw4bbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pause-circle3-filled" /></template>
