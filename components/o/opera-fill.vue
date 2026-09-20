<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnae6_w-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnae6_w-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:opera-fill" /></template>
