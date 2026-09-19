<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm4l_5_0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm4l_5_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tulip" /></template>
