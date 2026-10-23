<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xawi8xb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xawi8xb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:rows-2" /></template>
