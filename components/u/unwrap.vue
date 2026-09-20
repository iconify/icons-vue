<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-5ht6mav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-5ht6mav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unwrap" /></template>
