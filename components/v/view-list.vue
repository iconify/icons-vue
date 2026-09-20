<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lasvxn6gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lasvxn6gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:view-list" /></template>
