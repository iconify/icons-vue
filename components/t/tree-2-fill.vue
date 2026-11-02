<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng0cel71x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng0cel71x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-2-fill" /></template>
