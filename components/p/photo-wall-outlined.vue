<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6_4-sbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6_4-sbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:photo-wall-outlined" /></template>
