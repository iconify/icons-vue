<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf8pw_b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qf8pw_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:view-rows" /></template>
