<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgdd18btl.css';
import '../../css/y/y2ci2rbgk.css';
import '../../css/p/pkw90xu3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgdd18btl"/><path class="y2ci2rbgk"/><path class="pkw90xu3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:performance-tablet-increase-bold" /></template>
