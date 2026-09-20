<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f66pyacbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f66pyacbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scroll-to-bottom-fill" /></template>
