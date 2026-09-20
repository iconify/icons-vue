<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzod95b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzod95b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rewind-5" /></template>
