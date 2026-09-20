<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqi6xjbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gqi6xjbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trophy" /></template>
