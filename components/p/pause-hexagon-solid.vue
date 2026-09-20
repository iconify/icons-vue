<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b624cwaib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b624cwaib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-hexagon-solid" /></template>
