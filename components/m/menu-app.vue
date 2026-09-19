<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbxw48pzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbxw48pzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:menu-app" /></template>
