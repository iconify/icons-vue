<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc32zrb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc32zrb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:unlink" /></template>
