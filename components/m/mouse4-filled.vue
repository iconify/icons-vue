<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsw-4vbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw-4vbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mouse4-filled" /></template>
