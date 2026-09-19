<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7eeyiwkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g7eeyiwkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:sign-in" /></template>
