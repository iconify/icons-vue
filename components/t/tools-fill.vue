<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc_h33bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc_h33bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tools-fill" /></template>
