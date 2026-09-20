<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt9xsy.css';
import '../../css/u/uh4u4q.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt9xsy"/><circle class="uh4u4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch" /></template>
