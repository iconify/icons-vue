<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_vn7mhbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="g_vn7mhbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squaresettings" /></template>
