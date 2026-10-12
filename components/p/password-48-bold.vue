<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiqj48bop.css';
import '../../css/a/ahgdhlcfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yiqj48bop"/><path class="ahgdhlcfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:password-48-bold" /></template>
