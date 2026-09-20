<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6v5r2biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6v5r2biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:menu-application" /></template>
