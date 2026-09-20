<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq0cprbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq0cprbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:opera-mini" /></template>
