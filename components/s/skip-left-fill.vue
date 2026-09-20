<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imo3q5bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imo3q5bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-left-fill" /></template>
