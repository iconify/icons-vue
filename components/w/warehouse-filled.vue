<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yellpjx9e.css';
import '../../css/l/l8r0bab9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yellpjx9e"/><path class="l8r0bab9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:warehouse-filled" /></template>
