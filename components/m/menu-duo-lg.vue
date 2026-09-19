<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctcl7tbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctcl7tbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-duo-lg" /></template>
