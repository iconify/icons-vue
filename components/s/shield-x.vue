<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wugs2qmcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wugs2qmcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-x" /></template>
