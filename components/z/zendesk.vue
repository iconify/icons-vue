<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb0rhnbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xb0rhnbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zendesk" /></template>
