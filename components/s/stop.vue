<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxswfgjtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rxswfgjtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stop" /></template>
