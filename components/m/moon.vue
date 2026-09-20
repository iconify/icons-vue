<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly42ygbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ly42ygbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:moon" /></template>
