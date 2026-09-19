<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikq9_k5ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1760,"height":1792};
const content = `<path class="ikq9_k5ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort-amount-desc" /></template>
