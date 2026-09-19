<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz0aqo5pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz0aqo5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:messenger" /></template>
