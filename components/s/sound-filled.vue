<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk1mjebnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk1mjebnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sound-filled" /></template>
