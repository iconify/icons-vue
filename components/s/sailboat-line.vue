<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atmx8dpqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmx8dpqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sailboat-line" /></template>
