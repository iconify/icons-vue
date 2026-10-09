<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yak9gybyx.css';
import '../../css/f/ftk0oxb7p.css';
import '../../css/z/z2iqjbiby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yak9gybyx"/><path class="ftk0oxb7p"/><path class="z2iqjbiby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tractor-20-bold" /></template>
