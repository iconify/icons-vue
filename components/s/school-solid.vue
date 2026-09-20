<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk29hzl3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qk29hzl3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:school-solid" /></template>
