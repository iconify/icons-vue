<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4-jmxyye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="t4-jmxyye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tag" /></template>
