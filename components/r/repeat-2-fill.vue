<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygdn8ccah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygdn8ccah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:repeat-2-fill" /></template>
