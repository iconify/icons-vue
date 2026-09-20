<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zizw0eb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zizw0eb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sprout" /></template>
