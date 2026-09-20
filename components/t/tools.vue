<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap_-e3b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap_-e3b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tools" /></template>
