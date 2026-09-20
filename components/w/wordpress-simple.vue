<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkrzjhblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkrzjhblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wordpress-simple" /></template>
