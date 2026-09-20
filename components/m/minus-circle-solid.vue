<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7-xs6b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7-xs6b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:minus-circle-solid" /></template>
