<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/o/o3rybj.css';
import '../../css/j/j8ttiv.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c o3rybj"/><path class="a0m25c j8ttiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:round-ramp-left" /></template>
