<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqkh_cb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqkh_cb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sigma-48-bold" /></template>
