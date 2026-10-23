<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6rj7ac-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6rj7ac-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:webcam" /></template>
