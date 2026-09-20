<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve5zjyb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ve5zjyb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-flat-outline" /></template>
