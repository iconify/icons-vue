<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zttyezb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zttyezb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:paw-print" /></template>
