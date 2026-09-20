<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntitz-80y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="ntitz-80y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:moon-half-right-5" /></template>
