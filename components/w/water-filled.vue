<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcf5jt.css';
import '../../css/w/w1kvfb.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-22.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcf5jt"/><path class="w1kvfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:water-filled" /></template>
