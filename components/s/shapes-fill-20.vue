<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn705c-7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sn705c-7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shapes-fill-20" /></template>
