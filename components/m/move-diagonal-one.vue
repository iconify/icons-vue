<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hua0ulbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hua0ulbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:move-diagonal-one" /></template>
