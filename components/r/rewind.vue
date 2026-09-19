<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx0y_snju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx0y_snju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rewind" /></template>
