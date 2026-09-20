<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdsu2bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-9,"top":-2};
const content = `<path class="lgdsu2bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:more-vertical" /></template>
