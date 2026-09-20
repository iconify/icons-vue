<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp5lk3b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kp5lk3b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:panty" /></template>
