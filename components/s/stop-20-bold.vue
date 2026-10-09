<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyywebrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="odyywebrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stop-20-bold" /></template>
