<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubzx9fbaa.css';
import '../../css/d/dlqc4jbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ubzx9fbaa"/><path class="dlqc4jbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unread-16" /></template>
