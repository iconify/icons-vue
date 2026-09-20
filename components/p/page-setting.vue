<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_fb8gn8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_fb8gn8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:page-setting" /></template>
