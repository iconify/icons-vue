<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoj__nbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yoj__nbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:radiopublic" /></template>
