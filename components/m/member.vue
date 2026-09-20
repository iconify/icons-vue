<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af72pmb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af72pmb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:member" /></template>
