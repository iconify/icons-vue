<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erhbn3bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erhbn3bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:work-off-filled" /></template>
