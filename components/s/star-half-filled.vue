<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc-b3s.css';
import '../../css/c/chdxye.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc-b3s"/><path class="chdxye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-half-filled" /></template>
