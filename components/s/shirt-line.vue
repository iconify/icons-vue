<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfo48gy5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfo48gy5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shirt-line" /></template>
