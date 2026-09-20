<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf-ki8wwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kf-ki8wwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:volume-off" /></template>
