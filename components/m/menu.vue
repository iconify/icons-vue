<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgi_h6bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi_h6bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:menu" /></template>
