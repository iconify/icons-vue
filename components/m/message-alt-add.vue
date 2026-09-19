<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpr9a6b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpr9a6b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-alt-add" /></template>
