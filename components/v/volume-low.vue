<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0hbrfbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c0hbrfbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:volume-low" /></template>
