<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omt7_bbav.css';
import '../../css/y/ymie1nvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="omt7_bbav"/><path class="ymie1nvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-frigid" /></template>
