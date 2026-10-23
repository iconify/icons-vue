<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7ry0b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7ry0b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:music" /></template>
