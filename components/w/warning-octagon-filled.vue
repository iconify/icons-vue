<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd1c23p7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1c23p7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-octagon-filled" /></template>
