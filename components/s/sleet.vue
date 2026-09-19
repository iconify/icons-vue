<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rclnhcb_b.css';
import '../../css/z/z9u1ekeoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rclnhcb_b"/><path class="z9u1ekeoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sleet" /></template>
