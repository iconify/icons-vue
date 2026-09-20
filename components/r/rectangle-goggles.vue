<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfc5xouoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfc5xouoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rectangle-goggles" /></template>
