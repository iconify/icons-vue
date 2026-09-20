<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waq0mlnar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waq0mlnar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-setting-fill" /></template>
