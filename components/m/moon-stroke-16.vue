<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgi1i3bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cgi1i3bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-stroke-16" /></template>
