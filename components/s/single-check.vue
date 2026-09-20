<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6ulnw8uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p6ulnw8uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:single-check" /></template>
