<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9ryfb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9ryfb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tiktok-line" /></template>
