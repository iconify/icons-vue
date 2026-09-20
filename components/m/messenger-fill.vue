<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icu7sb6yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icu7sb6yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:messenger-fill" /></template>
