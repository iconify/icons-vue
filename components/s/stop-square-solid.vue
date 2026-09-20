<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv717gnze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv717gnze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-square-solid" /></template>
