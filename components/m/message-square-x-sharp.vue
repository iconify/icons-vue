<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob86dxngx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob86dxngx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-x-sharp" /></template>
