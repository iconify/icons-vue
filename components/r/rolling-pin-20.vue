<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfsmapzzo.css';
import '../../css/v/vkz5pbbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bfsmapzzo"/><path class="vkz5pbbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rolling-pin-20" /></template>
