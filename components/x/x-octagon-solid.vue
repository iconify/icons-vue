<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8xrzubfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8xrzubfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-octagon-solid" /></template>
