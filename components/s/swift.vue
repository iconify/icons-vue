<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef8-76t7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ef8-76t7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:swift" /></template>
