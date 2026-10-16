<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt6-vgweh.css';
import '../../css/y/yu6035bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gt6-vgweh"/><path class="yu6035bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wrap-text-20-bold" /></template>
