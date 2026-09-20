<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj9e8_bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj9e8_bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:more-2-fill" /></template>
