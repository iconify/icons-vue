<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/easx_7mjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="easx_7mjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:map" /></template>
