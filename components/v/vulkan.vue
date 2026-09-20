<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0g57acut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g57acut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vulkan" /></template>
