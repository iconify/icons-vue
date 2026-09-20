<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr-6avbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-6avbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-reverse-fill" /></template>
