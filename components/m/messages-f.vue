<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfg3yjb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="vfg3yjb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:messages-f" /></template>
