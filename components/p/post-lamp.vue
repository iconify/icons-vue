<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdwjyjwwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdwjyjwwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-lamp" /></template>
