<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxg4r3bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxg4r3bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:motorbike" /></template>
