<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksbvw3bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ksbvw3bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:volume-up" /></template>
