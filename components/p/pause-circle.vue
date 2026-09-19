<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-kvwzx-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x-kvwzx-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pause-circle" /></template>
