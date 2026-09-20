<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylfm_3b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylfm_3b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:planet" /></template>
