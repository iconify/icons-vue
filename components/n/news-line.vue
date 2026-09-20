<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygzihvbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygzihvbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:news-line" /></template>
