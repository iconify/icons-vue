<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfao2sbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfao2sbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-octagon-solid" /></template>
