<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm4_6m-0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm4_6m-0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seat-passenger" /></template>
