<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef_uqabxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ef_uqabxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-x-light" /></template>
