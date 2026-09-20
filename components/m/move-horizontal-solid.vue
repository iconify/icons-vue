<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyrvkswcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyrvkswcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:move-horizontal-solid" /></template>
