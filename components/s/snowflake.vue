<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml0h7rsel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ml0h7rsel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:snowflake" /></template>
