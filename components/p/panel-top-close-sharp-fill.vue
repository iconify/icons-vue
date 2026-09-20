<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtfl3gngu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtfl3gngu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-close-sharp-fill" /></template>
