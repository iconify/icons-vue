<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vifm8s9hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vifm8s9hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:suitcase-xray" /></template>
