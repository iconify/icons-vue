<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt39edbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt39edbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:watch" /></template>
