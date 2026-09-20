<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqq92b05g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqq92b05g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spectrum-line" /></template>
