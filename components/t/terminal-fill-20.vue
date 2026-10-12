<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oolx-sbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oolx-sbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-fill-20" /></template>
