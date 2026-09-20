<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukpjozb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukpjozb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tumblr-fill" /></template>
