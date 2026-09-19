<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h70xpjbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h70xpjbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:saucelabs" /></template>
