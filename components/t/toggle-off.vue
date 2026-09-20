<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6l_3sb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6l_3sb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:toggle-off" /></template>
