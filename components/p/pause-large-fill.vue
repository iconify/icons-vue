<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oteru_gyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oteru_gyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pause-large-fill" /></template>
