<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_jc7nyzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n_jc7nyzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:plugin" /></template>
