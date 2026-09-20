<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlvpz0bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlvpz0bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-solid" /></template>
