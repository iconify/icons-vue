<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1od4kbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1od4kbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:triangle" /></template>
