<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sezlb9bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sezlb9bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:question-mark" /></template>
