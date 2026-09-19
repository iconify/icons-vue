<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swf451boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="swf451boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:psltwo" /></template>
