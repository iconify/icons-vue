<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugd8dbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hugd8dbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tooth-solid" /></template>
