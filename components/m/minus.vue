<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt6v-jbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xt6v-jbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:minus" /></template>
