<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4m548dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fd4m548dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-text-outline" /></template>
