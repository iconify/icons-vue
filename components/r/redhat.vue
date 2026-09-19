<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe56f6bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe56f6bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:redhat" /></template>
