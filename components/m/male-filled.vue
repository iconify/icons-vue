<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dskl14byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dskl14byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:male-filled" /></template>
