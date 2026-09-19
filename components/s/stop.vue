<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddrfoxb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ddrfoxb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stop" /></template>
