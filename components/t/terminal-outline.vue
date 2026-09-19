<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elyxbx7ey.css';
import '../../css/r/r92xs4nql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="elyxbx7ey"/><path class="r92xs4nql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:terminal-outline" /></template>
