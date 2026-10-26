<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb44_r7uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lb44_r7uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:moon" /></template>
