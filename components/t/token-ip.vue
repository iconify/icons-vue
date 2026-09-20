<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy-wlb8oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dy-wlb8oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-ip" /></template>
