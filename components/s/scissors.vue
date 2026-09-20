<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cew5y9b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cew5y9b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:scissors" /></template>
