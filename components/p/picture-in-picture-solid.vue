<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjrjh7x3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjrjh7x3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:picture-in-picture-solid" /></template>
