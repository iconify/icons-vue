<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf8g6jb6t.css';
import '../../css/y/yrg7pgb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf8g6jb6t"/><path class="yrg7pgb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-2-bold-duotone" /></template>
