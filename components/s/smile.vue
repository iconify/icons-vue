<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvx8sibzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvx8sibzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smile" /></template>
