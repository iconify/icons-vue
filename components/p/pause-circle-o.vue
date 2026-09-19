<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw2yiybqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="yw2yiybqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pause-circle-o" /></template>
