<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hss7tib0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hss7tib0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:paintbrush" /></template>
