<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu9u31ebu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xu9u31ebu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:send-alt-filled" /></template>
