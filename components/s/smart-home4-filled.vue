<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zujffeb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zujffeb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-home4-filled" /></template>
