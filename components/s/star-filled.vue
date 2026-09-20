<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmewq3_yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmewq3_yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:star-filled" /></template>
