<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlui4r1hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlui4r1hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shining-line" /></template>
