<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxc7n1kon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc7n1kon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wallet" /></template>
