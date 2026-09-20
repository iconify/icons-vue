<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt_rr58_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jt_rr58_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:templ" /></template>
