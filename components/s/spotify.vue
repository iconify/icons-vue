<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnduabl5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rnduabl5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:spotify" /></template>
