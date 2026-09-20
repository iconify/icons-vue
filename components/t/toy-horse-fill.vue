<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r560ybvhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r560ybvhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toy-horse-fill" /></template>
