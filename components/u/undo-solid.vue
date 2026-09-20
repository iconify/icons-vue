<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk81-zpyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk81-zpyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:undo-solid" /></template>
