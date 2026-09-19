<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxiue0b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxiue0b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification-deactivated" /></template>
