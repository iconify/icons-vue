<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amdrchs6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="amdrchs6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:notification-email" /></template>
