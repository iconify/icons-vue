<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7t-cc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dy7t-cc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:urgency-filled" /></template>
