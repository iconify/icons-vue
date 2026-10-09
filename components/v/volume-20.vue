<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcyh21bht.css';
import '../../css/i/iuy7adb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dcyh21bht"/><path class="iuy7adb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-20" /></template>
