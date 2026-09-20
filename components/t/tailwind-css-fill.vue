<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsvkrrtht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsvkrrtht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tailwind-css-fill" /></template>
