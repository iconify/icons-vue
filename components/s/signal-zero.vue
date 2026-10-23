<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6x3acfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6x3acfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signal-zero" /></template>
