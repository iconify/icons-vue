<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdwzv5bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdwzv5bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:venmo" /></template>
