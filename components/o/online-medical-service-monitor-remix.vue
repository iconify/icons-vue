<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxchu0bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jxchu0bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:online-medical-service-monitor-remix" /></template>
