<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb5foabvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yb5foabvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:twenty-four-hour-support-filled" /></template>
