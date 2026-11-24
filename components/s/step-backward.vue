<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/serxr9lmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="serxr9lmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:step-backward" /></template>
