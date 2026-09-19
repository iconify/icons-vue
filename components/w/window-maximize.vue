<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xopn4tb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xopn4tb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:window-maximize" /></template>
