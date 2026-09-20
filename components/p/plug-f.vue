<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfbmbcpyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-1.5};
const content = `<path class="dfbmbcpyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:plug-f" /></template>
