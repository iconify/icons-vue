<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anp_7vq1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="anp_7vq1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:th-list-solid" /></template>
