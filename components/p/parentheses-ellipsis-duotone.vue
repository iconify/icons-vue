<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkkt6hb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vkkt6hb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parentheses-ellipsis-duotone" /></template>
