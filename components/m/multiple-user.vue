<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiek2ibjp.css';
import '../../css/t/tml6j6bpx.css';
import '../../css/c/ctqpb75vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aiek2ibjp"/><path class="tml6j6bpx"/><path class="ctqpb75vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:multiple-user" /></template>
