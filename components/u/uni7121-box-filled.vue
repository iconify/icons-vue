<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3m5hu29g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e3m5hu29g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni7121-box-filled" /></template>
