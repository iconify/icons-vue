<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uouj_4bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":496};
const content = `<path class="uouj_4bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pizza" /></template>
